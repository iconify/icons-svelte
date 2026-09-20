<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5auws.css';
import '../../css/i/iw1iew.css';
import '../../css/l/lc9ssn.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-66.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5auws iw1iew"/><path class="iw1iew lc9ssn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:minus-square-twotone" {...props}></Icon>
