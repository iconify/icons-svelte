<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be8scfowa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="be8scfowa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:molecules-outlined" {...props}></Icon>
