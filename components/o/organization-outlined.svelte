<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi-wf1bll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mi-wf1bll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:organization-outlined" {...props}></Icon>
