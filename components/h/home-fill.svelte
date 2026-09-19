<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8bf7_9ae.css';
import '../../css/w/wmc2ozbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8bf7_9ae"/><path class="wmc2ozbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:home-fill" {...props}></Icon>
