<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mudut7hiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mudut7hiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-bottom-sharp" {...props}></Icon>
