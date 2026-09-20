<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4patjbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s4patjbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:moustache-solid" {...props}></Icon>
