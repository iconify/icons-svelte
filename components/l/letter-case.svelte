<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob47p4bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob47p4bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-case" {...props}></Icon>
