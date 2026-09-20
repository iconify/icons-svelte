<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3i8dxbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="l3i8dxbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:contact-phonebook-solid" {...props}></Icon>
