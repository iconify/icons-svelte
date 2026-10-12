<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adm1b9bzj.css';
import '../../css/s/sizbx91ge.css';
import '../../css/i/iwbhkacly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="adm1b9bzj"/><path class="sizbx91ge"/><path class="iwbhkacly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paste-48-bold" {...props}></Icon>
