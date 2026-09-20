<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/diuciquml.css';
import '../../css/q/qy_x9db4g.css';
import '../../css/o/olk_csb2h.css';
import '../../css/z/zsw5drbid.css';
import '../../css/w/wzubvnb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="diuciquml"/><path class="qy_x9db4g"/><path class="olk_csb2h"/><path class="zsw5drbid"/><path class="wzubvnb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:bibliography" {...props}></Icon>
