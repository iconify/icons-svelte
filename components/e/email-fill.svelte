<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knqzh0wlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="knqzh0wlw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:email-fill" {...props}></Icon>
