<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2ldvwbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2ldvwbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:question-solid" {...props}></Icon>
