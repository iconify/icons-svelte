<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7k9mhc2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a7k9mhc2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:clipboard-alt-fill" {...props}></Icon>
