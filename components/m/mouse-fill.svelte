<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr0hxdh-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qr0hxdh-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:mouse-fill" {...props}></Icon>
