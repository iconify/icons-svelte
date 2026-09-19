<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu7me6ans.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu7me6ans"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:octpus" {...props}></Icon>
