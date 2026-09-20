<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi5syqv6f.css';
import '../../css/y/ynooprbfx.css';
import '../../css/d/dhmi6ubno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi5syqv6f"/><path class="ynooprbfx"/><path clip-rule="evenodd" class="dhmi6ubno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:calendar" {...props}></Icon>
