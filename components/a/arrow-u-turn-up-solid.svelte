<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1jtxjbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1jtxjbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-u-turn-up-solid" {...props}></Icon>
