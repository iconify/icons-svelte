<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj4pyrh1t.css';
import '../../css/h/h0-fzyzmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vj4pyrh1t"/><path class="h0-fzyzmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:heyform-dark" {...props}></Icon>
