<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzm_txj8c.css';
import '../../css/g/gqct9gbdf.css';
import '../../css/i/ib9od1bqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yzm_txj8c"/><circle class="gqct9gbdf"/><path class="ib9od1bqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:ribbon-sharp" {...props}></Icon>
