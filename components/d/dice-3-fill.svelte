<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi94q_tnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gi94q_tnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:dice-3-fill" {...props}></Icon>
