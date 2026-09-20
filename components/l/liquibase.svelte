<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn_tx-8bl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nn_tx-8bl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:liquibase" {...props}></Icon>
