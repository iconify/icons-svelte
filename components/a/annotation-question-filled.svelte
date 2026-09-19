<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6k1uib-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6k1uib-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:annotation-question-filled" {...props}></Icon>
