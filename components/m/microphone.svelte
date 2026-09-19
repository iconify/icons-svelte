<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7tjhpahb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7tjhpahb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:microphone" {...props}></Icon>
