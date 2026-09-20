<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj8dkmkmu.css';
import '../../css/m/mvmn2eb4z.css';
import '../../css/n/nvr0ynxmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xj8dkmkmu"/><path class="mvmn2eb4z"/><path class="nvr0ynxmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-calendar-dark" {...props}></Icon>
