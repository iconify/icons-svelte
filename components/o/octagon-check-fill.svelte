<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh4vwnbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vh4vwnbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:octagon-check-fill" {...props}></Icon>
