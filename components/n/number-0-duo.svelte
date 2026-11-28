<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sarxmn0sl.css';
import '../../css/l/lnc1wrb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sarxmn0sl secondary"/><path class="lnc1wrb5i primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-0-duo" {...props}></Icon>
