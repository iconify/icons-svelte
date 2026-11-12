<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snixp0b7u.css';
import '../../css/b/b-02yv13v.css';
import '../../css/n/nvr0ynxmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="snixp0b7u"/><path class="b-02yv13v"/><path class="nvr0ynxmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-calendar-dark" {...props}></Icon>
