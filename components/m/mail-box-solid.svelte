<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cww7qob_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cww7qob_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:mail-box-solid" {...props}></Icon>
