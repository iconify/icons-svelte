<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j16jsh-6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j16jsh-6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:lactation-24px" {...props}></Icon>
