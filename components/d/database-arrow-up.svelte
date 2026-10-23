<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfnyr6eve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfnyr6eve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:database-arrow-up" {...props}></Icon>
