<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1iew.css';
import '../../css/s/sgi08m.css';
import '../../css/y/y4wbml.css';
import '../../css/p/pciifw.css';
import '../../css/f/fhjy5e.css';
import '../../css/o/oyeo5a.css';
import '../../css/s/so-from-62.css';
import '../../css/f/fade-to-1.css';
import '../../css/d/d-_-jasl.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew sgi08m y4wbml"/><path class="iw1iew pciifw"/><path class="fhjy5e iw1iew y4wbml"/><path class="iw1iew oyeo5a y4wbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:file-document" {...props}></Icon>
