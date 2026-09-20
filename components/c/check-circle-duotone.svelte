<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x63fcn5tz.css';
import '../../css/t/tymptoban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x63fcn5tz"/><path class="tymptoban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:check-circle-duotone" {...props}></Icon>
