<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eff8rj4kv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eff8rj4kv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bug" {...props}></Icon>
