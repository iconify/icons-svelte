<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efizyogne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efizyogne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:password-user" {...props}></Icon>
