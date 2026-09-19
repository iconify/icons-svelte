<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2o7jubrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z2o7jubrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:leg-24px" {...props}></Icon>
