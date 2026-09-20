<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy37zibmr.css';
import '../../css/o/o15ae4bpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sy37zibmr"/><path class="o15ae4bpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:convoy" {...props}></Icon>
