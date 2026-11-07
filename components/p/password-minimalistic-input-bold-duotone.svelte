<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqt3vmb-u.css';
import '../../css/j/jjt0fksdh.css';
import '../../css/o/om59irbzs.css';
import '../../css/k/k62rgabws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqt3vmb-u"/><path class="jjt0fksdh"/><path class="om59irbzs"/><path class="k62rgabws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:password-minimalistic-input-bold-duotone" {...props}></Icon>
