<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htcr3kb3h.css';
import '../../css/a/ajkq-sngp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="htcr3kb3h"/><path class="ajkq-sngp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dropout" {...props}></Icon>
