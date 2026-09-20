<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4-a4tbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4-a4tbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:inbox-24" {...props}></Icon>
