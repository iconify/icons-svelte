<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/q/qtq3h6bch.css';
import '../../css/q/qez094buu.css';
import '../../css/w/wzga5cc5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qtq3h6bch"/><path class="qez094buu"/><circle class="wzga5cc5k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:file-archive" {...props}></Icon>
