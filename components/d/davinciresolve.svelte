<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7nmlpbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7nmlpbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:davinciresolve" {...props}></Icon>
