<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt9l_-hve.css';
import '../../css/g/gazl242lv.css';
import '../../css/q/qw8mp2b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pt9l_-hve"/><path class="gazl242lv"/><path clip-rule="evenodd" class="qw8mp2b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:monitor-smartphone-bold" {...props}></Icon>
