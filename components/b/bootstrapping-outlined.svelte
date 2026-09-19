<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh10aeonn.css';
import '../../css/t/t08gpvbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh10aeonn"/><path class="t08gpvbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:bootstrapping-outlined" {...props}></Icon>
