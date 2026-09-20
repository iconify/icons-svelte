<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn7x6o.css';
import '../../css/i/iw1iew.css';
import '../../css/g/g_t0ty.css';
import '../../css/y/y4wbml.css';
import '../../css/v/v562ka.css';
import '../../css/s/so-from-54.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cn7x6o iw1iew"/><path class="g_t0ty iw1iew y4wbml"/><path class="iw1iew v562ka y4wbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:brake-filled" {...props}></Icon>
