<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doe0tki7y.css';
import '../../css/m/m7pfecc5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="doe0tki7y"/><path class="m7pfecc5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:badge-check" {...props}></Icon>
