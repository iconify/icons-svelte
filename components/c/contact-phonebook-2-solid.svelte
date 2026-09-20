<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph965gbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ph965gbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:contact-phonebook-2-solid" {...props}></Icon>
