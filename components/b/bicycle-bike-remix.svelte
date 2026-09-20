<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_vz_ub6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v_vz_ub6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:bicycle-bike-remix" {...props}></Icon>
