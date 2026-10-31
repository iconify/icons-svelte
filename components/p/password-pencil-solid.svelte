<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_yofr8-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v_yofr8-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:password-pencil-solid" {...props}></Icon>
