<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc7-hhdgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kc7-hhdgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:layout-right-sidebar-solid" {...props}></Icon>
