<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqdzmsb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cqdzmsb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:linkedin-outline" {...props}></Icon>
