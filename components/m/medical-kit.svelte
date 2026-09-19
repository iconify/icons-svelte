<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox5bagm_m.css';
import '../../css/a/a-uqmqb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox5bagm_m"/><path class="a-uqmqb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:medical-kit" {...props}></Icon>
