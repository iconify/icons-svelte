<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eajcmacpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eajcmacpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:inbox-solid" {...props}></Icon>
