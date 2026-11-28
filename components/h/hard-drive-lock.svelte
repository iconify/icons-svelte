<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qahqiebfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qahqiebfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:hard-drive-lock" {...props}></Icon>
