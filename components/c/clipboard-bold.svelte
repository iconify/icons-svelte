<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8epyabtk.css';
import '../../css/v/v696jcbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8epyabtk"/><path clip-rule="evenodd" class="v696jcbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-bold" {...props}></Icon>
