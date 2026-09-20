<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coqzlbc7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="coqzlbc7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:dovecot" {...props}></Icon>
