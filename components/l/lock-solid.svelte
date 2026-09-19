<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4bk5tbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n4bk5tbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:lock-solid" {...props}></Icon>
