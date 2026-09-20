<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7rjambcu.css';
import '../../css/a/au92l6bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7rjambcu"/><path class="au92l6bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:anubis" {...props}></Icon>
