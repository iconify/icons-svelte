<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7ifvc6jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n7ifvc6jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:layout-window-25-solid" {...props}></Icon>
