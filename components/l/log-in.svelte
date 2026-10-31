<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/f/fono4sb0u.css';
import '../../css/g/glfu-ulem.css';
import '../../css/j/jn3ayb5ag.css';
import '../../css/w/w5qn3c7ko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="fono4sb0u wm-shadow"/><path class="glfu-ulem wm-shadow"/><path class="jn3ayb5ag"/><path class="w5qn3c7ko"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:log-in" {...props}></Icon>
