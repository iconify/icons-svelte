<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5ica_b2j.css';
import '../../css/i/irrkctldn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w5ica_b2j"/><path class="irrkctldn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:book-2-bold" {...props}></Icon>
