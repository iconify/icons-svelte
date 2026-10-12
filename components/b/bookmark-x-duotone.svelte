<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v1vtpvbwr.css';
import '../../css/p/p395msbuh.css';
import '../../css/e/emg88iban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v1vtpvbwr"/><path class="p395msbuh"/><path class="emg88iban"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bookmark-x-duotone" {...props}></Icon>
