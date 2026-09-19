<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anrpz00wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anrpz00wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:alarm-add" {...props}></Icon>
