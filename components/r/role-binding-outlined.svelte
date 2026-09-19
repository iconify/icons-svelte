<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b03zqx2zz.css';
import '../../css/h/h6r-0zwfg.css';
import '../../css/i/iu9qj1lar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b03zqx2zz"/><path class="h6r-0zwfg"/><path class="iu9qj1lar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:role-binding-outlined" {...props}></Icon>
