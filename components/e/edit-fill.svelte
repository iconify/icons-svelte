<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2xeqddgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w2xeqddgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:edit-fill" {...props}></Icon>
