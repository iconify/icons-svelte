<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/s/s1rnuy7eq.css';
import '../../css/f/fxuyefsgp.css';
import '../../css/b/b73ocondb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s1rnuy7eq"/><path class="fxuyefsgp"/><path class="b73ocondb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:kettle" {...props}></Icon>
