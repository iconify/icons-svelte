<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti696rbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti696rbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:direction-up-right" {...props}></Icon>
