<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqn_rxbsq.css';
import '../../css/m/mq1ufp71u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jqn_rxbsq"/><path class="mq1ufp71u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:controller" {...props}></Icon>
