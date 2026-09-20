<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adzm42zuk.css';
import '../../css/s/s8ope8btg.css';
import '../../css/p/pp0f03bez.css';
import '../../css/q/q8h4qbb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="adzm42zuk"/><path class="s8ope8btg"/><path class="pp0f03bez"/><path class="q8h4qbb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nasa" {...props}></Icon>
