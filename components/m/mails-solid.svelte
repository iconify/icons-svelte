<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqnqrx4dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqnqrx4dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mails-solid" {...props}></Icon>
