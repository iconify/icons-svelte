<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf-d8gb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cf-d8gb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:clipboard-cancel" {...props}></Icon>
