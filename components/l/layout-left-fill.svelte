<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6zygktec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6zygktec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-left-fill" {...props}></Icon>
