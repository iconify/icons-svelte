<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imkwy3-et.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":454,"height":735};
const content = `<path class="imkwy3-et"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:l-upper-case" {...props}></Icon>
