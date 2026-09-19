<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g89yo4bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g89yo4bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-group-centura" {...props}></Icon>
