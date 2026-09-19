<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-bufnlro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-bufnlro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:hfml-felix" {...props}></Icon>
