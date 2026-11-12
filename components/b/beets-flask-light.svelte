<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-8zeib9o.css';
import '../../css/g/gncr9mbaq.css';
import '../../css/s/s8i3jsm2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="v-8zeib9o"/><path class="gncr9mbaq"/><path class="s8i3jsm2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beets-flask-light" {...props}></Icon>
