<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok_erpmtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ok_erpmtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pail" {...props}></Icon>
