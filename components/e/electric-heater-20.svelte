<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc0nz7arf.css';
import '../../css/f/fu6k9ir6c.css';
import '../../css/g/g29n01b-u.css';
import '../../css/y/y4eq8bc3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rc0nz7arf"/><path class="fu6k9ir6c"/><path class="g29n01b-u"/><path class="y4eq8bc3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-heater-20" {...props}></Icon>
