<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz8cebuhr.css';
import '../../css/i/igmbzigbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sz8cebuhr"/><path class="igmbzigbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nutalert" {...props}></Icon>
