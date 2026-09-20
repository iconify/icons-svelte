<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/p/pri320nxf.css';
import '../../css/h/hana-fm8g.css';
import '../../css/b/b6ymlcrjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="pri320nxf"/><circle class="hana-fm8g"/><path class="b6ymlcrjg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cam-web-solid" {...props}></Icon>
