<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yptv8empz.css';
import '../../css/e/e7ebmvq0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yptv8empz"/><path class="e7ebmvq0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:globe-timezone-solid" {...props}></Icon>
