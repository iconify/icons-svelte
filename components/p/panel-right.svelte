<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi9plq57p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi9plq57p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:panel-right" {...props}></Icon>
