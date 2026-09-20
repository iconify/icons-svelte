<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogvcoqbcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogvcoqbcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:idea" {...props}></Icon>
