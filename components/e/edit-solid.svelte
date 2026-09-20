<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irx4tpg6l.css';
import '../../css/x/x7l00djaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irx4tpg6l"/><path class="x7l00djaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:edit-solid" {...props}></Icon>
