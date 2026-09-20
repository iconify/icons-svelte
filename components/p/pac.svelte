<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_9tr3bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_9tr3bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pac" {...props}></Icon>
