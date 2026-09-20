<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awy6hv8rm.css';
import '../../css/x/xxg6e85ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awy6hv8rm"/><path class="xxg6e85ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kmon" {...props}></Icon>
