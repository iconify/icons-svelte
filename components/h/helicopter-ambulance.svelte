<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvjqu111s.css';
import '../../css/g/g91n7nble.css';
import '../../css/h/h6_9nma6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvjqu111s"/><path class="g91n7nble"/><path class="h6_9nma6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:helicopter-ambulance" {...props}></Icon>
