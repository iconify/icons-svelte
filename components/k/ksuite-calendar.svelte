<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4ir8ob_w.css';
import '../../css/t/tsou7sbms.css';
import '../../css/u/uzxwg9bba.css';
import '../../css/g/g4ssyewpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x4ir8ob_w"/><path class="tsou7sbms"/><path class="uzxwg9bba"/><path class="g4ssyewpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-calendar" {...props}></Icon>
