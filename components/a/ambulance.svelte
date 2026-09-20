<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bju99-9zx.css';
import '../../css/p/pl4wrbb3x.css';
import '../../css/y/yhlbi21sm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="bju99-9zx"/><path class="pl4wrbb3x"/><path class="yhlbi21sm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:ambulance" {...props}></Icon>
