<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-qc0_vlp.css';
import '../../css/a/amj39fbui.css';
import '../../css/x/xvig2ib6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="v-qc0_vlp"/><path class="amj39fbui"/><path class="xvig2ib6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:gauge" {...props}></Icon>
