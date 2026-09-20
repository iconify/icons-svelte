<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/difapm_qv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="difapm_qv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bulb" {...props}></Icon>
