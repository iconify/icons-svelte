<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/q/qa3-8i7to.css';
import '../../css/o/o9zmhp_zw.css';
import '../../css/z/zfy9cb6vk.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGg056GeQx"><g class="hv130ab-t"><path class="qa3-8i7to"/><path class="o9zmhp_zw"/><path class="zfy9cb6vk"/></g></mask></defs><path mask="url(#SVGg056GeQx)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:flight-airflow" {...props}></Icon>
