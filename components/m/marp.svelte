<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijmbp0vus.css';
import '../../css/t/td80pac2f.css';
import '../../css/h/h38q_tbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ijmbp0vus"/><path class="td80pac2f"/><path class="h38q_tbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:marp" {...props}></Icon>
