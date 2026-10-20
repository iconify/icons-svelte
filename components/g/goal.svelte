<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otjhl6bue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otjhl6bue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:goal" {...props}></Icon>
