<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8asty5qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q8asty5qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:battery-empty-outline" {...props}></Icon>
