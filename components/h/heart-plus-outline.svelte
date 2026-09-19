<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-qd2pbhi.css';
import '../../css/h/h2t_13bqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-qd2pbhi"/><path clip-rule="evenodd" class="h2t_13bqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:heart-plus-outline" {...props}></Icon>
