<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1ecxxb0z.css';
import '../../css/j/jor-usn7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1ecxxb0z"/><path class="jor-usn7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-down-left-square" {...props}></Icon>
