<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eusk0o6ap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":667,"height":688};
const content = `<path class="eusk0o6ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:eject" {...props}></Icon>
