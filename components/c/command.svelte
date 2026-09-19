<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-sd6dlux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-sd6dlux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:command" {...props}></Icon>
