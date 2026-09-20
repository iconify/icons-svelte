<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpqbj1buy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpqbj1buy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:copy-check-filled" {...props}></Icon>
