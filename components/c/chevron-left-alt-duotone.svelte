<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqaciybhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqaciybhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:chevron-left-alt-duotone" {...props}></Icon>
