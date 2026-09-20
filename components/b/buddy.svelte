<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv0cyhbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qv0cyhbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:buddy" {...props}></Icon>
