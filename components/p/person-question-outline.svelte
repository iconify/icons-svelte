<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_q5lupxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_q5lupxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:person-question-outline" {...props}></Icon>
