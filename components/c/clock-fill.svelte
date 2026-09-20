<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziiawdh2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ziiawdh2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:clock-fill" {...props}></Icon>
